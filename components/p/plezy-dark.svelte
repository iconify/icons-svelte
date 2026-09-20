<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qy9_b6x2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qy9_b6x2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:plezy-dark" {...props}></Icon>
