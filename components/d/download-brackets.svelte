<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrtofabkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lrtofabkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:download-brackets" {...props}></Icon>
