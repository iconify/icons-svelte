<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/id3e5ebcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="id3e5ebcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:google-drive-alt" {...props}></Icon>
