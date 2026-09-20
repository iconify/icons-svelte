<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9mz0in7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f9mz0in7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-reduce-line" {...props}></Icon>
