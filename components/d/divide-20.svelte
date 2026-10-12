<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ic2g5r53d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ic2g5r53d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:divide-20" {...props}></Icon>
