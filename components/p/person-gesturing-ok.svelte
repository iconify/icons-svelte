<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5j1k6bfd.css';
import '../../css/v/vgmnmwbyq.css';
import '../../css/z/z_lmsqylr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="k5j1k6bfd"/><path class="vgmnmwbyq"/><path class="z_lmsqylr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:person-gesturing-ok" {...props}></Icon>
