<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ex74vg5rh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ex74vg5rh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:microsoft-line" {...props}></Icon>
