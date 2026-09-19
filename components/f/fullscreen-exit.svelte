<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjfyme04j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pjfyme04j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:fullscreen-exit" {...props}></Icon>
