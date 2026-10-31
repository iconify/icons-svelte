<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5_5al_xm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m5_5al_xm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circle-arrow-down-right-fill-round" {...props}></Icon>
