<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xj6qa494z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xj6qa494z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:currency-usd-circle" {...props}></Icon>
