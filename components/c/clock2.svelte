<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4iv2zb2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s4iv2zb2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:clock2" {...props}></Icon>
