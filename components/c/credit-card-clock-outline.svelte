<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xc00k61ms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xc00k61ms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:credit-card-clock-outline" {...props}></Icon>
