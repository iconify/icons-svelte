<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9ae4_bfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a9ae4_bfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:bot-message-square" {...props}></Icon>
