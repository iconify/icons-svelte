<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lixnqjmku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lixnqjmku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:folder-video-fill" {...props}></Icon>
