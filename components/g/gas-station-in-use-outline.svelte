<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfe_d_2bd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mfe_d_2bd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:gas-station-in-use-outline" {...props}></Icon>
