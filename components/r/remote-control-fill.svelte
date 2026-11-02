<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfwuf0bgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bfwuf0bgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:remote-control-fill" {...props}></Icon>
