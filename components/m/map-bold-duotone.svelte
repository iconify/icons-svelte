<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xtpeb-edw.css';
import '../../css/c/csrkrnb5y.css';
import '../../css/l/lsxguc_1v.css';
import '../../css/b/bj30ulegm.css';
import '../../css/k/k756bi2wv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xtpeb-edw"><path class="csrkrnb5y"/><path class="lsxguc_1v"/></g><path class="bj30ulegm"/><path class="k756bi2wv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:map-bold-duotone" {...props}></Icon>
