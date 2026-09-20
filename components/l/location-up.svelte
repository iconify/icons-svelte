<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hm3777prm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hm3777prm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:location-up" {...props}></Icon>
