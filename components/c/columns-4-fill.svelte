<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgs_ek1rs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pgs_ek1rs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:columns-4-fill" {...props}></Icon>
