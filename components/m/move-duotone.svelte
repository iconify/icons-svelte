<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khn9nwoel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="khn9nwoel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:move-duotone" {...props}></Icon>
