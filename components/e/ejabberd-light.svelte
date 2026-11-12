<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y--ny7bfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y--ny7bfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ejabberd-light" {...props}></Icon>
