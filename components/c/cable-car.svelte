<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/a/ary2b4lnc.css';
import '../../css/k/k_isoy1xt.css';
import '../../css/y/ytr9bcb0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="ary2b4lnc"/><path class="k_isoy1xt"/><path class="ytr9bcb0t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cable-car" {...props}></Icon>
