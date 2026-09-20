<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yo8g0tjqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yo8g0tjqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:award-line" {...props}></Icon>
