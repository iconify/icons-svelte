<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8g-wib6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u8g-wib6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:bear-face" {...props}></Icon>
