<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yljdd-biq.css';
import '../../css/c/cqlg1elow.css';
import '../../css/m/mqymo7s1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yljdd-biq"/><path class="cqlg1elow"/><path class="mqymo7s1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:radicle-light" {...props}></Icon>
