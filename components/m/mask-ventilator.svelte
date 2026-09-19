<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qh3i9mbcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="qh3i9mbcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:mask-ventilator" {...props}></Icon>
