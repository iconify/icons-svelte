<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jddyy98pw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jddyy98pw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:align-bottom" {...props}></Icon>
