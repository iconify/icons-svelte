<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njdpvjbzg.css';
import '../../css/f/fmukgjbig.css';
import '../../css/j/jlr84fbeb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="njdpvjbzg"/><path class="fmukgjbig"/><path class="jlr84fbeb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pig-20" {...props}></Icon>
