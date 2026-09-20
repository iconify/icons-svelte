<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kk8ro-scp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kk8ro-scp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:appgallery" {...props}></Icon>
