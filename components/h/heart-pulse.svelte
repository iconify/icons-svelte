<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2owkl-9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n2owkl-9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:heart-pulse" {...props}></Icon>
