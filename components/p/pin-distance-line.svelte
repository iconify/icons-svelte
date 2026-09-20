<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5omk_79g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t5omk_79g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:pin-distance-line" {...props}></Icon>
