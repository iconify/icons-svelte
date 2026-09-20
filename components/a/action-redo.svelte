<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wn7g_cbkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="wn7g_cbkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:action-redo" {...props}></Icon>
