<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lraiwvujr.css';
import '../../css/c/c97n50bhy.css';
import '../../css/w/w21c98bra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lraiwvujr"/><path class="c97n50bhy"/><path class="w21c98bra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:proton-lumo-dark" {...props}></Icon>
