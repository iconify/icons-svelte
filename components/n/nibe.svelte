<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_cffibvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k_cffibvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:nibe" {...props}></Icon>
