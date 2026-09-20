<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgjys7brw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cgjys7brw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:emoji-baby-outline" {...props}></Icon>
