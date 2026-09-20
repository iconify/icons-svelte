<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmcp94bsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zmcp94bsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:party-popper" {...props}></Icon>
