<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gsp1cjdax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gsp1cjdax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:office-building-with-flag" {...props}></Icon>
