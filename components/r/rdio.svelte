<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4_y7wbsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q4_y7wbsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:rdio" {...props}></Icon>
