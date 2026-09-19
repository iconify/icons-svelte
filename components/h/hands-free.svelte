<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kn6u72xbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="kn6u72xbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:hands-free" {...props}></Icon>
