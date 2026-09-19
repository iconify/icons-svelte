<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/praux6byf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="praux6byf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:aqara-vibration" {...props}></Icon>
