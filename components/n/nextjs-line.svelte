<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxa473bks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mxa473bks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:nextjs-line" {...props}></Icon>
