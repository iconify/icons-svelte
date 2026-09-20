<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5i4e-nou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="z5i4e-nou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-walking-and-person-riding-bicycle-on-crosswalk" {...props}></Icon>
