<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/biuihtbcw.css';
import '../../css/n/nou84c3ti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="biuihtbcw"/><path class="nou84c3ti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:funnel-match-rtl" {...props}></Icon>
