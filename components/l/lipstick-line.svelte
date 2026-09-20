<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxb_82bqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rxb_82bqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:lipstick-line" {...props}></Icon>
