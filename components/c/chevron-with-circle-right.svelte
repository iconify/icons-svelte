<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtoyfe4sg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mtoyfe4sg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:chevron-with-circle-right" {...props}></Icon>
