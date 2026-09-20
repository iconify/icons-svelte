<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0w3pxcur.css';
import '../../css/h/h0rooab0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d0w3pxcur"/><path class="h0rooab0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rabbit-line" {...props}></Icon>
