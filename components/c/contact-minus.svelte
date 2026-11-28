<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xg5x5g5zt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xg5x5g5zt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:contact-minus" {...props}></Icon>
