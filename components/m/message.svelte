<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-q4edcor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j-q4edcor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:message" {...props}></Icon>
