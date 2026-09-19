<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixn_37yhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ixn_37yhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:paw-outline" {...props}></Icon>
