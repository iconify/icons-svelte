<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zks0hobcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zks0hobcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:entrance" {...props}></Icon>
