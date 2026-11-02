<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rak7p_bwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rak7p_bwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:grass-line" {...props}></Icon>
