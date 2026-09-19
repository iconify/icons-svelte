<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmw875old.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zmw875old"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:chevron-right" {...props}></Icon>
