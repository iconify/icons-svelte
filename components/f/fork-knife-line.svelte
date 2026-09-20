<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvgm96bxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fvgm96bxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fork-knife-line" {...props}></Icon>
