<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_5-m_blk.css';
import '../../css/r/rjoq2cbhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i_5-m_blk"/><path class="rjoq2cbhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rocket-20" {...props}></Icon>
