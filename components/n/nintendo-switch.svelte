<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co33ozbue.css';
import '../../css/p/piy19x2pb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="co33ozbue"/><path class="piy19x2pb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nintendo-switch" {...props}></Icon>
