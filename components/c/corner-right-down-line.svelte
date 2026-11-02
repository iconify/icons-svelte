<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e4b7o400g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e4b7o400g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:corner-right-down-line" {...props}></Icon>
