<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fb166jh2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fb166jh2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:corner-down-right-gloss" {...props}></Icon>
