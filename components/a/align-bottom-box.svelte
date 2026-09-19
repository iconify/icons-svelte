<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/snx51kbpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="snx51kbpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:align-bottom-box" {...props}></Icon>
