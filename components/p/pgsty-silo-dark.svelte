<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2k-n7s4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w2k-n7s4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pgsty-silo-dark" {...props}></Icon>
