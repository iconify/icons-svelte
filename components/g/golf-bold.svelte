<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wabkbdbsx.css';
import '../../css/u/unngw-ben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wabkbdbsx"/><path class="unngw-ben"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:golf-bold" {...props}></Icon>
