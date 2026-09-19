<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nayue9sxw.css';
import '../../css/v/vpnv4ccxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nayue9sxw"/><path class="vpnv4ccxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-ionic-outline" {...props}></Icon>
