<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywe4se04n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ywe4se04n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:hackster" {...props}></Icon>
