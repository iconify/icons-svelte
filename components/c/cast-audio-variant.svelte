<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0de14sug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r0de14sug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cast-audio-variant" {...props}></Icon>
