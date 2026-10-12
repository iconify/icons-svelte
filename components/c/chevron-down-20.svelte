<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wtwowz7gl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wtwowz7gl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:chevron-down-20" {...props}></Icon>
