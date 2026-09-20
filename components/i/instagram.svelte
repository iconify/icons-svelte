<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rw5pnvb2b.css';
import '../../css/c/c2wy4abda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rw5pnvb2b"/><path class="c2wy4abda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:instagram" {...props}></Icon>
