<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2agh85ja.css';
import '../../css/l/l0ifl0rlq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d2agh85ja"/><path class="l0ifl0rlq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:convoy-light" {...props}></Icon>
