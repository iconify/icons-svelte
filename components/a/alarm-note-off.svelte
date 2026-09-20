<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvy456baf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tvy456baf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:alarm-note-off" {...props}></Icon>
