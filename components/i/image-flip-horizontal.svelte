<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uljo4f1yo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":25};
const content = `<path class="uljo4f1yo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:image-flip-horizontal" {...props}></Icon>
