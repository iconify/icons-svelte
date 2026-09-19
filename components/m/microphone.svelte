<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwzbg8b2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="bwzbg8b2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:microphone" {...props}></Icon>
