<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1ooo089j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x1ooo089j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:arrow-down-right-waves-solid" {...props}></Icon>
