<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ef364zb4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ef364zb4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:apple-pay" {...props}></Icon>
