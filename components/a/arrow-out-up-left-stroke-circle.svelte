<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l6gvdlb7i.css';
import '../../css/f/fuq627b0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l6gvdlb7i"/><path class="fuq627b0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-out-up-left-stroke-circle" {...props}></Icon>
