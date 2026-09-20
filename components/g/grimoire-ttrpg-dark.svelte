<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ur2nqhb_s.css';
import '../../css/x/xmk3jccpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ur2nqhb_s"/><path class="xmk3jccpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:grimoire-ttrpg-dark" {...props}></Icon>
