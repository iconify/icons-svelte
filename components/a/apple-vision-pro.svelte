<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k66w0-bok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k66w0-bok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:apple-vision-pro" {...props}></Icon>
