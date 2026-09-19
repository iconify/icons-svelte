<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ryn_ssbhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ryn_ssbhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:f1-alt" {...props}></Icon>
