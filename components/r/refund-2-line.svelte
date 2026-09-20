<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g699qabqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g699qabqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:refund-2-line" {...props}></Icon>
