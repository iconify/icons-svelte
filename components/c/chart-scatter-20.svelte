<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9nmtab-x.css';
import '../../css/b/bkmbl7bof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="l9nmtab-x"/><path class="bkmbl7bof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-scatter-20" {...props}></Icon>
