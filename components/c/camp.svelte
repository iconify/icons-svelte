<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kka3obg5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kka3obg5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:camp" {...props}></Icon>
