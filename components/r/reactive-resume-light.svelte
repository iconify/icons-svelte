<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vkleqj0hc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vkleqj0hc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:reactive-resume-light" {...props}></Icon>
