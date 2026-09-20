<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmb1as-8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bmb1as-8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:cactus" {...props}></Icon>
