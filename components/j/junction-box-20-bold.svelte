<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vayamib1a.css';
import '../../css/u/ut922vv1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vayamib1a"/><path class="ut922vv1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:junction-box-20-bold" {...props}></Icon>
