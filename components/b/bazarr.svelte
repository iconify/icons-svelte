<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/in9lfx_ls.css';
import '../../css/w/wdn99oykn.css';
import '../../css/t/trzsg0bwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="in9lfx_ls"/><path class="wdn99oykn"/><path class="trzsg0bwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bazarr" {...props}></Icon>
