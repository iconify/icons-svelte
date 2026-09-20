<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4v_u2b7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x4v_u2b7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:fragrance-off" {...props}></Icon>
