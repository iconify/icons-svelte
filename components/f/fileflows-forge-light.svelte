<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f018v5y4u.css';
import '../../css/r/rofz_96kq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f018v5y4u"/><path class="rofz_96kq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fileflows-forge-light" {...props}></Icon>
