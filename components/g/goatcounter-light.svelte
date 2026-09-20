<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3tfe5b7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z3tfe5b7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:goatcounter-light" {...props}></Icon>
