<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9cl3ld3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="p9cl3ld3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:mail-options" {...props}></Icon>
