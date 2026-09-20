<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqz9wkbyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="oqz9wkbyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:leaf-outline" {...props}></Icon>
