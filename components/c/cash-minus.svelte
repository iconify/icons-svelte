<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czw58k73a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="czw58k73a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cash-minus" {...props}></Icon>
