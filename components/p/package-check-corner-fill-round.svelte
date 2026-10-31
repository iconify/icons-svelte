<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bl_m7_hhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bl_m7_hhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:package-check-corner-fill-round" {...props}></Icon>
