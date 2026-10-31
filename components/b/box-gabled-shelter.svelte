<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uj35rnq-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="uj35rnq-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:box-gabled-shelter" {...props}></Icon>
