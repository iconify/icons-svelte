<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s09wq-brk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s09wq-brk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:move-left" {...props}></Icon>
