<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ooddoerrv.css';
import '../../css/t/td92ekb3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ooddoerrv"/><path class="td92ekb3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:list-collapse-line" {...props}></Icon>
