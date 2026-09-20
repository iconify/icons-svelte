<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/klrib_4gm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="klrib_4gm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:letter-z-circle" {...props}></Icon>
