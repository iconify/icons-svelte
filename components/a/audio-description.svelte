<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/ba8_jhblq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2304,"height":1280};
const content = `<path class="ba8_jhblq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:audio-description" {...props}></Icon>
