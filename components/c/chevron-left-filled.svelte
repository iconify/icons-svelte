<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vo9ts0bej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vo9ts0bej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:chevron-left-filled" {...props}></Icon>
