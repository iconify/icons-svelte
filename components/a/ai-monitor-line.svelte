<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fs60f7byn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fs60f7byn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:ai-monitor-line" {...props}></Icon>
