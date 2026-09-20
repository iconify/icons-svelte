<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyht5ccdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vyht5ccdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-x-circle" {...props}></Icon>
