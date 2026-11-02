<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bshu6htoq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bshu6htoq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:notebook-2-fill" {...props}></Icon>
