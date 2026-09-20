<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyn1iab4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xyn1iab4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:loading-bold" {...props}></Icon>
