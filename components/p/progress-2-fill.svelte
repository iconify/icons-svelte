<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfzarh7wb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cfzarh7wb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:progress-2-fill" {...props}></Icon>
