<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixh9d53ff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":6,"height":16};
const content = `<path class="ixh9d53ff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:italic" {...props}></Icon>
