<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q45pn-bge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q45pn-bge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:dropbox" {...props}></Icon>
