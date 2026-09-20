<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcu9tlrct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kcu9tlrct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-right-thin" {...props}></Icon>
