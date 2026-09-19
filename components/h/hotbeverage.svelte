<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzpan3bci.css';
import '../../css/o/ovgcn15iq.css';
import '../../css/k/kw6ok-jlw.css';
import '../../css/c/cforkdjpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pzpan3bci"/><path class="ovgcn15iq"/><path class="kw6ok-jlw"/><path class="cforkdjpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:hotbeverage" {...props}></Icon>
