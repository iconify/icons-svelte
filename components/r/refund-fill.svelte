<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9sp3kblw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v9sp3kblw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:refund-fill" {...props}></Icon>
