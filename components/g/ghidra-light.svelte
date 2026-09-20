<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abv6fbbiq.css';
import '../../css/v/vy5mqsbys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="abv6fbbiq"/><path class="vy5mqsbys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ghidra-light" {...props}></Icon>
