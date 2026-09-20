<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yq3y2-bza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yq3y2-bza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:arrow-down-right-circle-solid" {...props}></Icon>
