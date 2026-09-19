<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/j/jye2-i80a.css';
import '../../css/k/kp9b5cb7o.css';
import '../../css/r/rd_p_sicu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="s9cl3zbei"><rect class="jye2-i80a"/><path class="kp9b5cb7o"/><path class="rd_p_sicu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:note-pad" {...props}></Icon>
