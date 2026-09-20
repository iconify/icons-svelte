<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0rob0b3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n0rob0b3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:redstone-federal-credit-union-dark" {...props}></Icon>
