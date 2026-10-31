<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwo7y5b1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wwo7y5b1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:letter-k-fill-round" {...props}></Icon>
