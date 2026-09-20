<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5skxtb6n.css';
import '../../css/n/njarltr6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="t5skxtb6n"/><path class="njarltr6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:log-in-rtl" {...props}></Icon>
