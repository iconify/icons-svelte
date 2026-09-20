<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-qwv2pri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n-qwv2pri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bitcoin-light" {...props}></Icon>
