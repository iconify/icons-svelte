<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_mzvy6rk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x_mzvy6rk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:close-small-16" {...props}></Icon>
