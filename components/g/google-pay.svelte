<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/luvrd72ph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="luvrd72ph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:google-pay" {...props}></Icon>
