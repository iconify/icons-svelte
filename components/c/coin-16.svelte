<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1_ko4blm.css';
import '../../css/x/xqqc18b0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j1_ko4blm"/><path clip-rule="evenodd" class="xqqc18b0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:coin-16" {...props}></Icon>
