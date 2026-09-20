<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i15wu7f2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="i15wu7f2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-outer-light-up-right" {...props}></Icon>
