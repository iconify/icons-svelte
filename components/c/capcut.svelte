<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbpv6pbxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gbpv6pbxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:capcut" {...props}></Icon>
