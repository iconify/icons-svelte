<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6fe5ngbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s6fe5ngbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:ai-generate" {...props}></Icon>
