<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ks9d45bwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ks9d45bwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:emoji-2-line" {...props}></Icon>
