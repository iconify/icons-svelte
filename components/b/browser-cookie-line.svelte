<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lajp-mbmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lajp-mbmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:browser-cookie-line" {...props}></Icon>
