<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yxvt694xb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yxvt694xb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:right-angle-arrow" {...props}></Icon>
