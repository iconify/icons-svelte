<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztx86cb2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ztx86cb2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:call-ringing-01" {...props}></Icon>
