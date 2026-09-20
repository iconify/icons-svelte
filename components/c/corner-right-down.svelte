<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmlxph0bl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tmlxph0bl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:corner-right-down" {...props}></Icon>
