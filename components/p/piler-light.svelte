<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ntw2ccbts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ntw2ccbts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:piler-light" {...props}></Icon>
