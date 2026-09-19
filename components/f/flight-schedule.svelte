<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjzjafblt.css';
import '../../css/j/ji95cg_id.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pjzjafblt"/><path class="ji95cg_id"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:flight-schedule" {...props}></Icon>
