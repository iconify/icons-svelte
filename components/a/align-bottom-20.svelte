<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0-d2gbnz.css';
import '../../css/b/bwrmw-1aq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c0-d2gbnz"/><path class="bwrmw-1aq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:align-bottom-20" {...props}></Icon>
