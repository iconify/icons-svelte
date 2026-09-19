<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jcncmhbph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jcncmhbph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:arrow-90deg-left" {...props}></Icon>
