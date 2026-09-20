<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hsi7l1byg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hsi7l1byg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:map-marker-shield" {...props}></Icon>
