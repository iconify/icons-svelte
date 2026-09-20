<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rs28jhbsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rs28jhbsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:3d-box" {...props}></Icon>
