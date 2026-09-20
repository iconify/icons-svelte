<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ynq_iix5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ynq_iix5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:code-fill" {...props}></Icon>
