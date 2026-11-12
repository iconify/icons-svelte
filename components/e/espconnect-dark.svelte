<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etg9crbrk.css';
import '../../css/i/ipz9c_5nj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="etg9crbrk"/><path class="ipz9c_5nj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:espconnect-dark" {...props}></Icon>
