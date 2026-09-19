<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/u/u2ffjhxgz.css';
import '../../css/b/bgh9y3bsn.css';
import '../../css/l/lsle5sbqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><circle class="u2ffjhxgz"/><path class="bgh9y3bsn"/><path class="lsle5sbqv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:lock-keyhole-open" {...props}></Icon>
