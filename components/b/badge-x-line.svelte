<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lv55x9vmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lv55x9vmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:badge-x-line" {...props}></Icon>
