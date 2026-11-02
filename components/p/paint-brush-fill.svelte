<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-o4rlbhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-o4rlbhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:paint-brush-fill" {...props}></Icon>
