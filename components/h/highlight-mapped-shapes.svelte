<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lu_ffmb3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="lu_ffmb3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:highlight-mapped-shapes" {...props}></Icon>
