<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j73zm9bhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="j73zm9bhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-up-right-stipple" {...props}></Icon>
