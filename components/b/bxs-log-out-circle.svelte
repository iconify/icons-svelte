<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/waa9zhbgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="waa9zhbgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-log-out-circle" {...props}></Icon>
