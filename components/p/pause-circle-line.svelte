<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nyzcv3rvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nyzcv3rvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pause-circle-line" {...props}></Icon>
