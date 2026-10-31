<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzvr2u07d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kzvr2u07d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:fullscreen-exit-duotone-round" {...props}></Icon>
