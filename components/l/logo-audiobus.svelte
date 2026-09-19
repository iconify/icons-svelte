<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cg08evbls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="cg08evbls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:logo-audiobus" {...props}></Icon>
