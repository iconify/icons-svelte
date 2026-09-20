<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ypwzazrln.css';
import '../../css/d/dr7uw4h1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ypwzazrln"/><path class="dr7uw4h1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:laptop-smiley-1-bold" {...props}></Icon>
