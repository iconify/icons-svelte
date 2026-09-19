<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwrozcc_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dwrozcc_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:footprints" {...props}></Icon>
