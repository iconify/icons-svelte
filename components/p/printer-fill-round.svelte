<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fb-pknbdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fb-pknbdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:printer-fill-round" {...props}></Icon>
