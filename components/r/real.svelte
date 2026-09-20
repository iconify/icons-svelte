<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iupyxnbgc.css';
import '../../css/m/mabwzbbvc.css';
import '../../css/c/cj8-pez3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="iupyxnbgc"/><path class="mabwzbbvc"/><path class="cj8-pez3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:real" {...props}></Icon>
