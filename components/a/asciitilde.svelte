<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k27hhsbcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":508,"height":614};
const content = `<path class="k27hhsbcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:asciitilde" {...props}></Icon>
