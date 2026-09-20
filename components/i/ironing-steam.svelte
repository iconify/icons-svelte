<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rae37_bzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rae37_bzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:ironing-steam" {...props}></Icon>
