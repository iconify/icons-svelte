<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gz27hpnpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":96,"height":96};
const content = `<path class="gz27hpnpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:freescout-light" {...props}></Icon>
