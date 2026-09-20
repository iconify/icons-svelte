<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_6lnbbvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y_6lnbbvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:calendar-1-filled" {...props}></Icon>
