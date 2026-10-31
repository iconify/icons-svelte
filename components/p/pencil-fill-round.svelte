<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjd-bfbwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rjd-bfbwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:pencil-fill-round" {...props}></Icon>
