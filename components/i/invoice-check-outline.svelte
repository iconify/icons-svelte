<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zsz0_wapm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zsz0_wapm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:invoice-check-outline" {...props}></Icon>
