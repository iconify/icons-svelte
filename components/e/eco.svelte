<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ds2j1pnfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ds2j1pnfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:eco" {...props}></Icon>
