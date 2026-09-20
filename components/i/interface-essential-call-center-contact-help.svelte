<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1v0-0b8q.css';
import '../../css/w/wlj0jptgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="y1v0-0b8q"/><path class="wlj0jptgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-call-center-contact-help" {...props}></Icon>
