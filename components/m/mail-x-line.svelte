<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cyoc15fbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cyoc15fbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:mail-x-line" {...props}></Icon>
