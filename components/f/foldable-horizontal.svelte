<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfzj1le7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sfzj1le7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:foldable-horizontal" {...props}></Icon>
