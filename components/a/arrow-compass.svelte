<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/icxlooygs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="icxlooygs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-compass" {...props}></Icon>
