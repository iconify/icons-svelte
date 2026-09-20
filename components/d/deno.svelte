<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cp7ufvbwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cp7ufvbwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:deno" {...props}></Icon>
