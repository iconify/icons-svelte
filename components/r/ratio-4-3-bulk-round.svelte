<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qw4zn3u8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qw4zn3u8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:ratio-4-3-bulk-round" {...props}></Icon>
