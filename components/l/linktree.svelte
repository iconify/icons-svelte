<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4e783_3e.css';
import '../../css/v/vq5z-rl-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z4e783_3e"/><path class="vq5z-rl-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:linktree" {...props}></Icon>
