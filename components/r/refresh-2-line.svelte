<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sa79hshgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sa79hshgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:refresh-2-line" {...props}></Icon>
