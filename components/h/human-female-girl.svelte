<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvt3r3ygm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vvt3r3ygm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:human-female-girl" {...props}></Icon>
