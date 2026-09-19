<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckg1p6biu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ckg1p6biu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:incoming-call" {...props}></Icon>
