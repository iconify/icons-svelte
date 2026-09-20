<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bh9r02b-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bh9r02b-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:rollerblade-off" {...props}></Icon>
