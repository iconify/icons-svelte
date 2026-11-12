<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twe_8u5bv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="twe_8u5bv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pf2etools-dark" {...props}></Icon>
