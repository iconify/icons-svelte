<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6l4_zbwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w6l4_zbwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:crop" {...props}></Icon>
