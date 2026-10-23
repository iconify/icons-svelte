<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u80-kbcaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u80-kbcaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:bridge" {...props}></Icon>
