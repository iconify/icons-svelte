<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mywcv6bea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mywcv6bea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:message-square-plus" {...props}></Icon>
