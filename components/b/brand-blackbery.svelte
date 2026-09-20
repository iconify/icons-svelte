<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bv_x2xbvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bv_x2xbvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-blackbery" {...props}></Icon>
