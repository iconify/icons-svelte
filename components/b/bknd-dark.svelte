<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uk7b67bxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uk7b67bxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bknd-dark" {...props}></Icon>
