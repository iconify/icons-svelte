<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6dc5-vlc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="x6dc5-vlc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:id-badge" {...props}></Icon>
