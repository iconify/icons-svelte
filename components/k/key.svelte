<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whtqf2epm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="whtqf2epm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:key" {...props}></Icon>
