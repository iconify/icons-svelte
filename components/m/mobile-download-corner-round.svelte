<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9pzk5bwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e9pzk5bwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:mobile-download-corner-round" {...props}></Icon>
