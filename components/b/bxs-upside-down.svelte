<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwlm1_b0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wwlm1_b0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-upside-down" {...props}></Icon>
