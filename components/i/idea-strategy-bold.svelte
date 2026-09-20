<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4i1vwbhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r4i1vwbhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:idea-strategy-bold" {...props}></Icon>
