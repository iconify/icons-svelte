<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmkzp2pqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="lmkzp2pqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:control-play" {...props}></Icon>
