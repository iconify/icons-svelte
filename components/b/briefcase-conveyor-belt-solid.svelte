<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aw23jeecu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aw23jeecu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:briefcase-conveyor-belt-solid" {...props}></Icon>
