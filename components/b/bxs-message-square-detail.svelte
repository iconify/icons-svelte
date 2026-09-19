<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7oi56bnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t7oi56bnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-message-square-detail" {...props}></Icon>
