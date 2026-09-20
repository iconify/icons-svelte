<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijwgb3btt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ijwgb3btt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:pin-line" {...props}></Icon>
