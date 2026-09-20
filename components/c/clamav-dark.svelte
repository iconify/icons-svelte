<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ny62x4bxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ny62x4bxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:clamav-dark" {...props}></Icon>
