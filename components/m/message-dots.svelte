<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3l7-nubk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r3l7-nubk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:message-dots" {...props}></Icon>
