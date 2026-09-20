<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6g-zobdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x6g-zobdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:event-blank-outline" {...props}></Icon>
