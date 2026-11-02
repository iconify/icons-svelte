<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zkg31wasg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zkg31wasg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:minimize-line" {...props}></Icon>
