<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fyc5tabsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fyc5tabsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:currency-eur" {...props}></Icon>
