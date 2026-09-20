<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l0sruib_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l0sruib_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:cross-filled-16" {...props}></Icon>
