<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nyflosb7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nyflosb7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:libraries" {...props}></Icon>
