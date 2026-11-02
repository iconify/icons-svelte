<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xumdxw0gs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xumdxw0gs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:indoor-rowing-fill" {...props}></Icon>
