<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0-arvhnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d0-arvhnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:group-3-line" {...props}></Icon>
