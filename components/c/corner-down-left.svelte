<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gml7996sg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gml7996sg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:corner-down-left" {...props}></Icon>
