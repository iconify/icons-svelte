<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkjmr59pn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wkjmr59pn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:kazakhstani-tenge" {...props}></Icon>
