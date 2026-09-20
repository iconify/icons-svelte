<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7xh53b0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r7xh53b0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:edit-pen-4-line" {...props}></Icon>
