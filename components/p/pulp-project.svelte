<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkwkh496s.css';
import '../../css/u/u8-785b1v.css';
import '../../css/b/bni3nanaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gkwkh496s"/><path class="u8-785b1v"/><path class="bni3nanaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pulp-project" {...props}></Icon>
