<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kixgq6lls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kixgq6lls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:podium-outline" {...props}></Icon>
