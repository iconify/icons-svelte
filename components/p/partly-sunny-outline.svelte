<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htohhkvke.css';
import '../../css/b/bixpb61-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="htohhkvke"/><path class="bixpb61-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:partly-sunny-outline" {...props}></Icon>
