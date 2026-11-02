<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qh-wn-bou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qh-wn-bou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bone-line" {...props}></Icon>
