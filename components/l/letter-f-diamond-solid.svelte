<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wg9f7bbqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wg9f7bbqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-f-diamond-solid" {...props}></Icon>
