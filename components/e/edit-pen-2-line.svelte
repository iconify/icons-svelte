<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rb61kbyba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rb61kbyba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:edit-pen-2-line" {...props}></Icon>
