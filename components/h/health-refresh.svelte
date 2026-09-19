<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fo1owij7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="fo1owij7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:health-refresh" {...props}></Icon>
