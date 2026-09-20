<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xhb1mqwuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xhb1mqwuj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:invoice-arrow-right" {...props}></Icon>
