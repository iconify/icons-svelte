<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5ud2xbhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j5ud2xbhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:original-size-fill-16" {...props}></Icon>
