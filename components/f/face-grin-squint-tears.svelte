<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1tpi1b0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q1tpi1b0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:face-grin-squint-tears" {...props}></Icon>
