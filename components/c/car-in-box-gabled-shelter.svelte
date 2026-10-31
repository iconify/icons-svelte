<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0acmdbqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="b0acmdbqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:car-in-box-gabled-shelter" {...props}></Icon>
