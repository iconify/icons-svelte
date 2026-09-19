<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tg6p86m_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tg6p86m_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:ffmpeg" {...props}></Icon>
