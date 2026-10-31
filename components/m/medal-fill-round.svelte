<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/llgholb1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="llgholb1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:medal-fill-round" {...props}></Icon>
