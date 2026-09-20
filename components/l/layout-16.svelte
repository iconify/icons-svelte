<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlk56mgjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jlk56mgjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nonicons:layout-16" {...props}></Icon>
