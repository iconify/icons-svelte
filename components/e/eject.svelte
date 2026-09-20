<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxu2bz8el.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mxu2bz8el"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:eject" {...props}></Icon>
