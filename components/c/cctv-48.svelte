<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tc-samsdi.css';
import '../../css/m/mmi04ob3v.css';
import '../../css/m/mbxjymbwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tc-samsdi"/><path class="mmi04ob3v"/><path class="mbxjymbwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cctv-48" {...props}></Icon>
