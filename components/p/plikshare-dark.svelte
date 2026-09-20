<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eanui2ium.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eanui2ium"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:plikshare-dark" {...props}></Icon>
