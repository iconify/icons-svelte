<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nzzc_c6ad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nzzc_c6ad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:git-pages-light" {...props}></Icon>
