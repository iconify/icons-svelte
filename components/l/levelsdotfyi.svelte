<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsp0fcxhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xsp0fcxhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:levelsdotfyi" {...props}></Icon>
