<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/srif-ob_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="srif-ob_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:gift-round" {...props}></Icon>
