<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftn7tacln.css';
import '../../css/a/am_yeab8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ftn7tacln"/><path class="am_yeab8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:face-activated-add" {...props}></Icon>
