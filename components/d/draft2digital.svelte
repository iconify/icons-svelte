<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wf0bu9bgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":480,"height":512};
const content = `<path class="wf0bu9bgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:draft2digital" {...props}></Icon>
