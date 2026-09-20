<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5humm8bi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m5humm8bi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:lexware" {...props}></Icon>
