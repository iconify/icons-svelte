<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugtfc0auw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ugtfc0auw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:drinking-water" {...props}></Icon>
