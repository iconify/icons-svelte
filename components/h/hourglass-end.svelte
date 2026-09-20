<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3lmee8zj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="e3lmee8zj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:hourglass-end" {...props}></Icon>
