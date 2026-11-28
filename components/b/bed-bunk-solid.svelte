<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wm1mhvr8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wm1mhvr8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:bed-bunk-solid" {...props}></Icon>
