<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lctbntbyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lctbntbyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:firecracker" {...props}></Icon>
