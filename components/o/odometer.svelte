<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmk826btk.css';
import '../../css/x/xvjlt3b7b.css';
import '../../css/x/xdka2wbio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="hmk826btk"/><path class="xvjlt3b7b"/><path class="xdka2wbio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:odometer" {...props}></Icon>
