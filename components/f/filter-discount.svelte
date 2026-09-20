<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pu7x4t4ss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pu7x4t4ss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:filter-discount" {...props}></Icon>
