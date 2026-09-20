<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zawbwlbhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zawbwlbhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:movie-minus-outline" {...props}></Icon>
