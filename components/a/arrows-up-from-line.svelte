<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ll58u1lzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ll58u1lzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:arrows-up-from-line" {...props}></Icon>
