<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwznp_2kx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xwznp_2kx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-stackshare" {...props}></Icon>
