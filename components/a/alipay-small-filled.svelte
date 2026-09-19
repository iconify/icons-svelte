<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbnmv6zzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="nbnmv6zzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:alipay-small-filled" {...props}></Icon>
