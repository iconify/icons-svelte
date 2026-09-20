<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wtcj90bwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wtcj90bwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:arrow-big-down-left" {...props}></Icon>
