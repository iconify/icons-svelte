<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvs2y_6ct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="hvs2y_6ct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-round-up-right" {...props}></Icon>
