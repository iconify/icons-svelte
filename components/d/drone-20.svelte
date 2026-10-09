<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abchlonce.css';
import '../../css/q/qmetfmbtm.css';
import '../../css/g/gia1eubje.css';
import '../../css/e/e2y3avbgr.css';
import '../../css/x/x848z0w7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="abchlonce"/><path class="qmetfmbtm"/><path class="gia1eubje"/><path class="e2y3avbgr"/><path class="x848z0w7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:drone-20" {...props}></Icon>
