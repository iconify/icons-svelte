<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wc2n80bfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wc2n80bfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:history-solid" {...props}></Icon>
