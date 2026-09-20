<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whwdwc9ze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="whwdwc9ze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:move-horizontal" {...props}></Icon>
