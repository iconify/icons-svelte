<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfy11pvfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="gfy11pvfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrowtriangle-down" {...props}></Icon>
