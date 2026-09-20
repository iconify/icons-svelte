<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdh5gcb3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zdh5gcb3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-left-down-box-line" {...props}></Icon>
