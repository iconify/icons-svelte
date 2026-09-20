<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/onb2t3bho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="onb2t3bho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:attachment-2" {...props}></Icon>
