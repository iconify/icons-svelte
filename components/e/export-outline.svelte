<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s401l6b9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s401l6b9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:export-outline" {...props}></Icon>
