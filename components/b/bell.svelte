<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvqi0v3hc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tvqi0v3hc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:bell" {...props}></Icon>
