<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2eohmjnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k2eohmjnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:google-keep-logo-2-bold" {...props}></Icon>
