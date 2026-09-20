<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9nl6fbgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="x9nl6fbgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:desc" {...props}></Icon>
