<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6_oaacrp.css';
import '../../css/z/znp8eubox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o6_oaacrp"/><path class="znp8eubox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:medassist" {...props}></Icon>
