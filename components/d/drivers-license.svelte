<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wtaf1zbdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="wtaf1zbdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:drivers-license" {...props}></Icon>
