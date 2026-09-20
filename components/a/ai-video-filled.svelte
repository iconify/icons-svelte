<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u0cyckyfs.css';
import '../../css/l/llov8mbku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u0cyckyfs"/><path class="llov8mbku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:ai-video-filled" {...props}></Icon>
