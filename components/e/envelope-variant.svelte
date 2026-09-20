<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-xfzbb0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r-xfzbb0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:envelope-variant" {...props}></Icon>
