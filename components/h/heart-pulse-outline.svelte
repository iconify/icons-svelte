<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1oersbxq.css';
import '../../css/x/xmwn8lbyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f1oersbxq"/><path clip-rule="evenodd" class="xmwn8lbyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:heart-pulse-outline" {...props}></Icon>
