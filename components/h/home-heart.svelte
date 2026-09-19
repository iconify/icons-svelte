<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x03a93bun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x03a93bun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:home-heart" {...props}></Icon>
