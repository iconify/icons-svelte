<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/vor0eyoyz.css';
import '../../css/h/hnhmf1b1t.css';
import '../../css/i/i-unjrbqs.css';
import '../../css/o/o64dbibmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="vor0eyoyz"/><path class="hnhmf1b1t"/><path class="i-unjrbqs"/><path clip-rule="evenodd" class="o64dbibmw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:antibody-outline" {...props}></Icon>
