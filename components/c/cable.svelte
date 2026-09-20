<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-o21k_6n.css';
import '../../css/j/j3j2k6b7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="s-o21k_6n"/><path class="j3j2k6b7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:cable" {...props}></Icon>
