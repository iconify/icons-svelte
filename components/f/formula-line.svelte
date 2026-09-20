<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zolteabtf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zolteabtf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:formula-line" {...props}></Icon>
