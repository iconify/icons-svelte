<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esyyvmbvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="esyyvmbvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:abc-australia-news" {...props}></Icon>
