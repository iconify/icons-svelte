<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zk08rrbwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zk08rrbwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:mic-play" {...props}></Icon>
