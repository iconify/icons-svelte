<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7q6swbmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c7q6swbmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:avalanche-avax-fill" {...props}></Icon>
