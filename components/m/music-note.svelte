<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m87ck961u.css';
import '../../css/d/d1brjbccy.css';
import '../../css/d/d-xbejb9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m87ck961u"/><path class="d1brjbccy"/><path class="d-xbejb9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:music-note" {...props}></Icon>
