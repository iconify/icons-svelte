<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5r00xbem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l5r00xbem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:file-video-fill" {...props}></Icon>
