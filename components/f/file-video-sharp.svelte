<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvny9qbsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cvny9qbsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:file-video-sharp" {...props}></Icon>
