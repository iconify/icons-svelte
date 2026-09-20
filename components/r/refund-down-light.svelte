<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvaf3v5na.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wvaf3v5na"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:refund-down-light" {...props}></Icon>
