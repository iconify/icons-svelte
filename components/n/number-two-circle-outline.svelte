<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ow_d5dbav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ow_d5dbav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:number-two-circle-outline" {...props}></Icon>
