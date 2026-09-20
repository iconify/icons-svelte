<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksny98b8v.css';
import '../../css/a/ay56a163g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ksny98b8v"/><path class="ay56a163g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:new-window-rtl" {...props}></Icon>
