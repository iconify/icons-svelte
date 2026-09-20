<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxiza7bmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wxiza7bmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:arrow-big-left" {...props}></Icon>
