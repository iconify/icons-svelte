<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eour_gbjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eour_gbjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:archive-in" {...props}></Icon>
