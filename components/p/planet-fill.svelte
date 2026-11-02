<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x16vlc8os.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x16vlc8os"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:planet-fill" {...props}></Icon>
