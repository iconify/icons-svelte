<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2myycbsp.css';
import '../../css/p/pu43vbcbj.css';
import '../../css/a/a-8czfekn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r2myycbsp"/><path class="pu43vbcbj"/><path class="a-8czfekn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:file-clock-48" {...props}></Icon>
