<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8nfscbtn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u8nfscbtn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:live-photo-fill" {...props}></Icon>
