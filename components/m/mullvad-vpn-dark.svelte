<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nae4m6bdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nae4m6bdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mullvad-vpn-dark" {...props}></Icon>
