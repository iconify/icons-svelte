<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcs2ixboi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bcs2ixboi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:headset-round" {...props}></Icon>
