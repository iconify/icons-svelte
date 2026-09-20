<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubi-bbbak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ubi-bbbak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:download" {...props}></Icon>
