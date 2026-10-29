<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xpvnaqbdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xpvnaqbdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:bookmark" {...props}></Icon>
