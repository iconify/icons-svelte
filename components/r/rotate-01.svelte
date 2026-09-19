<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mn9vvrb-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mn9vvrb-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:rotate-01" {...props}></Icon>
