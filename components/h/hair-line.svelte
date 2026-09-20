<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1_wjijeg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i1_wjijeg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hair-line" {...props}></Icon>
