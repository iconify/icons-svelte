<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zhlsyklwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zhlsyklwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-drop-up-line" {...props}></Icon>
