<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_4r6fbdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k_4r6fbdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:refund-cny-line" {...props}></Icon>
