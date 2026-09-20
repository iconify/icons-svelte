<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vo5rrlbcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vo5rrlbcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:acer" {...props}></Icon>
