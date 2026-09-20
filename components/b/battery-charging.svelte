<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7m23ib4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q7m23ib4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:battery-charging" {...props}></Icon>
