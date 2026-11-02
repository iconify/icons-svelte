<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xicqsbbcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xicqsbbcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pen-2-line" {...props}></Icon>
