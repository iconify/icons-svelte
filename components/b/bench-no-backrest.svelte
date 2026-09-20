<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hn2rj9k1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hn2rj9k1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:bench-no-backrest" {...props}></Icon>
