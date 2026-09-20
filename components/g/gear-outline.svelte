<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgqr2umbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pgqr2umbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:gear-outline" {...props}></Icon>
