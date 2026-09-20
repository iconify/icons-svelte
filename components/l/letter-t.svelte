<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-j27gaxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t-j27gaxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:letter-t" {...props}></Icon>
