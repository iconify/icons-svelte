<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f7audcctd.css';
import '../../css/p/pah233ash.css';
import '../../css/w/whx3_cfkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f7audcctd"/><path class="pah233ash"/><path class="whx3_cfkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:auditorr" {...props}></Icon>
