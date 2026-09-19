<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tc-rd5b-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tc-rd5b-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:grav" {...props}></Icon>
