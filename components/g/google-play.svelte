<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcuxe76bp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bcuxe76bp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:google-play" {...props}></Icon>
