<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfiv3z6qi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zfiv3z6qi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mullvad-vpn-light" {...props}></Icon>
