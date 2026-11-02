<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f15g3fbrn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f15g3fbrn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:refresh-2-line" {...props}></Icon>
