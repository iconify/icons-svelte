<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ro-1ks86k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ro-1ks86k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:announcement-line" {...props}></Icon>
