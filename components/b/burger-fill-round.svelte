<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wv4g6ebah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wv4g6ebah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:burger-fill-round" {...props}></Icon>
