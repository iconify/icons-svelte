<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ma8i4wb3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ma8i4wb3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-sleeping-in-bed" {...props}></Icon>
