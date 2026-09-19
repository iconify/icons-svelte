<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a91t2_tvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":800,"height":850};
const content = `<path class="a91t2_tvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:dropbox" {...props}></Icon>
