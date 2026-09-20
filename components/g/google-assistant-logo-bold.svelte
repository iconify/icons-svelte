<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvtdb8fbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yvtdb8fbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:google-assistant-logo-bold" {...props}></Icon>
