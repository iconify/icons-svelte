<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7c9z5_wq.css';
import '../../css/k/kmcbvkrhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="b7c9z5_wq"/><path class="kmcbvkrhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:microphone-off-stroke-16" {...props}></Icon>
