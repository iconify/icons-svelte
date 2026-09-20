<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hpwzdblim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hpwzdblim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:home-report" {...props}></Icon>
