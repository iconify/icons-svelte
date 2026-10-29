<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vr_mp9f4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vr_mp9f4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:navigation" {...props}></Icon>
