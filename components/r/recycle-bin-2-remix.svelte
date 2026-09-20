<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rc5tu7bnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rc5tu7bnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:recycle-bin-2-remix" {...props}></Icon>
