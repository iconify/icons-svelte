<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ob8f3hzgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ob8f3hzgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-shopify" {...props}></Icon>
