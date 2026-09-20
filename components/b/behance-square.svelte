<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-o7_nfmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="u-o7_nfmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:behance-square" {...props}></Icon>
