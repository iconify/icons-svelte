<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxh_cwblb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hxh_cwblb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:ai-app-mac-sharp" {...props}></Icon>
