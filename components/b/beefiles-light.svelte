<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vascdch3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vascdch3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:beefiles-light" {...props}></Icon>
