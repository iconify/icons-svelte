<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbyywfnen.css';
import '../../css/h/hz4iidbyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lbyywfnen"/><path class="hz4iidbyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:baby-20-bold" {...props}></Icon>
