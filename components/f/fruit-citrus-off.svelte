<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ine0nfmfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ine0nfmfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:fruit-citrus-off" {...props}></Icon>
