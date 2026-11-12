<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgsu639mr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mgsu639mr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:link-down" {...props}></Icon>
