<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3ab64k_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x3ab64k_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:presentation-filled" {...props}></Icon>
