<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1lp2mbow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="w1lp2mbow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:hostel-14" {...props}></Icon>
