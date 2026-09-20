<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqkrn3bpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="rqkrn3bpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:clapperboard" {...props}></Icon>
