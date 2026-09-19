<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dte2kjhbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="dte2kjhbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:people" {...props}></Icon>
