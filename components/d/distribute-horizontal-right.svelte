<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bucsvihvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bucsvihvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:distribute-horizontal-right" {...props}></Icon>
