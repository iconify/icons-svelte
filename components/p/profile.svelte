<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yavxk_bsz.css';
import '../../css/i/ixpy7yyki.css';
import '../../css/p/pn-hlnbwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="yavxk_bsz"/><path class="ixpy7yyki"/><path class="pn-hlnbwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:profile" {...props}></Icon>
