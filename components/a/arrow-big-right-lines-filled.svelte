<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/depg8kbiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="depg8kbiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-big-right-lines-filled" {...props}></Icon>
