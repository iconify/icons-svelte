<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uejxkl2qs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uejxkl2qs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:microscope-fill" {...props}></Icon>
