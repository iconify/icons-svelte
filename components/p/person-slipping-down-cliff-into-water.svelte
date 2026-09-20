<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/js3nu1ssz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="js3nu1ssz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-slipping-down-cliff-into-water" {...props}></Icon>
