<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4ha_dcsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m4ha_dcsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:phone-end2-filled" {...props}></Icon>
