<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ey3ifmspw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ey3ifmspw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:bookmark-check-gloss" {...props}></Icon>
