<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qo_wluuda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qo_wluuda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:popcorn" {...props}></Icon>
