<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mq4li-2nf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mq4li-2nf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:message-plus" {...props}></Icon>
