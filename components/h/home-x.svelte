<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dltnu8-yl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dltnu8-yl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:home-x" {...props}></Icon>
