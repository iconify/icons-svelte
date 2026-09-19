<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nytrsfbyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nytrsfbyz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:roomslounge" {...props}></Icon>
