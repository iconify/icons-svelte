<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2r-6absw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="m2r-6absw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:bell" {...props}></Icon>
