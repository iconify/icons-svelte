<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aja--_w3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="aja--_w3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-double-horizontal-light-down" {...props}></Icon>
