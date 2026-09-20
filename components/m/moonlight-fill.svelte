<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjibmefbt.css';
import '../../css/r/rutj1thmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sjibmefbt"/><path class="rutj1thmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:moonlight-fill" {...props}></Icon>
