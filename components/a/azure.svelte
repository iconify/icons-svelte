<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/srt_3maoq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="srt_3maoq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:azure" {...props}></Icon>
