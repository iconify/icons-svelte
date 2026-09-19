<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iagiy7bpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="iagiy7bpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:collection-bookmark" {...props}></Icon>
