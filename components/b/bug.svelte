<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv-jkn1sc.css';
import '../../css/z/zz0-pccgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nv-jkn1sc"/><path class="zz0-pccgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:bug" {...props}></Icon>
