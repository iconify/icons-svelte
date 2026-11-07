<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4b0zsbme.css';
import '../../css/q/q9j565bpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l4b0zsbme"/><path class="q9j565bpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:armchair-2-bold" {...props}></Icon>
