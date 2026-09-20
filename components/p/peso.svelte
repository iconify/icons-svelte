<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqjltqlri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cqjltqlri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:peso" {...props}></Icon>
