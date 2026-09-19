<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dbj9wxbdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dbj9wxbdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:bow-and-arrow" {...props}></Icon>
