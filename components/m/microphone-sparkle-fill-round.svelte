<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzfeosixy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zzfeosixy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:microphone-sparkle-fill-round" {...props}></Icon>
