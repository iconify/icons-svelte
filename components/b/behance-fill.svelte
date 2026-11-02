<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dq3npfbvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dq3npfbvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:behance-fill" {...props}></Icon>
