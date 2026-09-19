<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gu-rojbqe.css';
import '../../css/n/n6od47b6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="gu-rojbqe"/><path class="n6od47b6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:microphone-off-stroke-12" {...props}></Icon>
