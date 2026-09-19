<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kj2fl5b5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kj2fl5b5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:google-wifi-router" {...props}></Icon>
