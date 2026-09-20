<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ux06hx6gz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ux06hx6gz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:inbox-line" {...props}></Icon>
