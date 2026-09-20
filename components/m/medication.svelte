<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4xm99bte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="t4xm99bte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:medication" {...props}></Icon>
