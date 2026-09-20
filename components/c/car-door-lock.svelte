<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wd61v6brm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wd61v6brm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:car-door-lock" {...props}></Icon>
