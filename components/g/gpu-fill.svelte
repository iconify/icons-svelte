<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2-ab0bdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t2-ab0bdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:gpu-fill" {...props}></Icon>
