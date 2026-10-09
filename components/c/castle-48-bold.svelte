<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oz0-7c0kb.css';
import '../../css/j/jf0anfbvm.css';
import '../../css/r/r9l9x_bxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="oz0-7c0kb"/><path class="jf0anfbvm"/><path class="r9l9x_bxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:castle-48-bold" {...props}></Icon>
