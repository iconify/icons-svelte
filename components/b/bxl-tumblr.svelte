<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dlvy82buf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dlvy82buf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-tumblr" {...props}></Icon>
