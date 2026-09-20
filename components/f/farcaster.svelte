<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mk0dc_oca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mk0dc_oca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:farcaster" {...props}></Icon>
