<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gr-sxkt2n.css';
import '../../css/p/poccklbbx.css';
import '../../css/h/hhujsxb0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gr-sxkt2n"/><path class="poccklbbx"/><path class="hhujsxb0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pipe-wrench-20-bold" {...props}></Icon>
