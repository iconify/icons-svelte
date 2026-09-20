<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fj0_dtb-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fj0_dtb-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:notification-bing-filled" {...props}></Icon>
