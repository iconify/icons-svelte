<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvr5zlrke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fvr5zlrke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:beef-line" {...props}></Icon>
