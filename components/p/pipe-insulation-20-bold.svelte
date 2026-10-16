<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qlo4be-zl.css';
import '../../css/l/lswyakbtp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qlo4be-zl"/><path class="lswyakbtp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pipe-insulation-20-bold" {...props}></Icon>
