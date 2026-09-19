<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovslp8rsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ovslp8rsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:reply-mirrored" {...props}></Icon>
