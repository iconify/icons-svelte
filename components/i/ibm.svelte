<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2zosibgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b d2zosibgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:ibm" {...props}></Icon>
