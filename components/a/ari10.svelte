<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4necybef.css';
import '../../css/a/a4z6_-bfl.css';
import '../../css/f/f3u9p6fad.css';
import '../../css/n/n62mo89yv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r4necybef"/><path clip-rule="evenodd" class="a4z6_-bfl"/><path class="f3u9p6fad"/><path clip-rule="evenodd" class="n62mo89yv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ari10" {...props}></Icon>
