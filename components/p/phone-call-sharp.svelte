<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpmxqib-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wpmxqib-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:phone-call-sharp" {...props}></Icon>
