<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ru3g04bdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ru3g04bdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:plus-square" {...props}></Icon>
