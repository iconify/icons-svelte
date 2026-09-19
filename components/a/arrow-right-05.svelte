<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pnx5eo-_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pnx5eo-_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:arrow-right-05" {...props}></Icon>
