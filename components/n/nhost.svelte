<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ah7geomkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":273};
const content = `<path class="ah7geomkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:nhost" {...props}></Icon>
