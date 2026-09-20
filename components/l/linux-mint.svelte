<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m03k8sbdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m03k8sbdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:linux-mint" {...props}></Icon>
