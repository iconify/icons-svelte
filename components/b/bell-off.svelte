<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eh13lxl6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eh13lxl6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:bell-off" {...props}></Icon>
