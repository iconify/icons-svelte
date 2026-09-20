<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lzp-f_lps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lzp-f_lps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:arrow-repeat-outline" {...props}></Icon>
