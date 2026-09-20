<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfai0924n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sfai0924n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bell-alert-outline" {...props}></Icon>
