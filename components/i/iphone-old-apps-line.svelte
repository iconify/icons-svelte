<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ktndi-n6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ktndi-n6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:iphone-old-apps-line" {...props}></Icon>
