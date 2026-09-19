<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cyto10bys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cyto10bys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:distribute-horizontal-center" {...props}></Icon>
