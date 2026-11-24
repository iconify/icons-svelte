<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wsnt9mslf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wsnt9mslf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:leafy-green-filled" {...props}></Icon>
