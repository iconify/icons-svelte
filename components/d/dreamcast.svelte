<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_u43vbek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z_u43vbek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:dreamcast" {...props}></Icon>
