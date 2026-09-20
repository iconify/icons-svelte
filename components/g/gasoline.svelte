<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrxkk9bcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zrxkk9bcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:gasoline" {...props}></Icon>
