<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdy-a-bvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cdy-a-bvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:history-line" {...props}></Icon>
