<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shrl-vx_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="shrl-vx_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:radarr" {...props}></Icon>
