<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixx1zab_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ixx1zab_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:log-out" {...props}></Icon>
