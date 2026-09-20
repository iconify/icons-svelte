<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drynjrbjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="drynjrbjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:bicycle-key" {...props}></Icon>
