<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_n-dbbym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q_n-dbbym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:mingcute-line" {...props}></Icon>
