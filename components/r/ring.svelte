<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qf0nq7tms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qf0nq7tms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:ring" {...props}></Icon>
