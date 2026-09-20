<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wd_s0sb-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wd_s0sb-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pepperminty-wiki-light" {...props}></Icon>
