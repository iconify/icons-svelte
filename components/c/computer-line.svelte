<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vnwadbbks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vnwadbbks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:computer-line" {...props}></Icon>
