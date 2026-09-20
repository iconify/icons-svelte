<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ass7ltv7w.css';
import '../../css/c/cu4o4vbry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ass7ltv7w"/><path clip-rule="evenodd" class="cu4o4vbry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:danmaku-off-fill" {...props}></Icon>
