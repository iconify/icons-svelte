<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uajmqcs3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uajmqcs3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:board-fill" {...props}></Icon>
