<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx8wksbhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="jx8wksbhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:computer-mouse" {...props}></Icon>
