<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nqh5xmk8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nqh5xmk8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nextbeats-dark" {...props}></Icon>
