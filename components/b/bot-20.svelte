<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_7m__7bi.css';
import '../../css/e/er5teobrz.css';
import '../../css/l/lmc5jxf9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z_7m__7bi"/><path class="er5teobrz"/><path class="lmc5jxf9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bot-20" {...props}></Icon>
