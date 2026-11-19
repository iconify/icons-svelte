<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xuob1e_hs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xuob1e_hs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:dartboard" {...props}></Icon>
