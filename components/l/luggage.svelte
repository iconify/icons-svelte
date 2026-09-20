<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbcz6wiur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vbcz6wiur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:luggage" {...props}></Icon>
