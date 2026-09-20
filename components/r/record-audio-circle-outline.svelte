<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_9bwc3ik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b_9bwc3ik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:record-audio-circle-outline" {...props}></Icon>
