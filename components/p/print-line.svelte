<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nq17t3gbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nq17t3gbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:print-line" {...props}></Icon>
