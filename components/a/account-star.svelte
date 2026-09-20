<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yxk6mbbjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yxk6mbbjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:account-star" {...props}></Icon>
