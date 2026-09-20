<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yp0p2xbzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yp0p2xbzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:message-minus-fill" {...props}></Icon>
