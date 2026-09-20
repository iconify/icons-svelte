<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o25rrxbqg.css';
import '../../css/k/ky67sqbnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o25rrxbqg"/><path class="ky67sqbnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:adventurelog-dark" {...props}></Icon>
