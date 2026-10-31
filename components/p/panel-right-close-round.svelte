<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wce1258hs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wce1258hs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:panel-right-close-round" {...props}></Icon>
