<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nkkp8_bwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nkkp8_bwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:nanoleaf-hex-grain" {...props}></Icon>
