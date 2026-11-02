<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vl_edabcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vl_edabcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:finger-swipe-line" {...props}></Icon>
