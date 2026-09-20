<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y2k65lump.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y2k65lump"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:pinterest-solid" {...props}></Icon>
