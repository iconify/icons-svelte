<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/geuvedbeg.css';
import '../../css/z/z1o1gjbgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="geuvedbeg"/><path class="z1o1gjbgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:calendar-arrow-up-filled" {...props}></Icon>
