<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p0e-t8bma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p0e-t8bma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:brain" {...props}></Icon>
