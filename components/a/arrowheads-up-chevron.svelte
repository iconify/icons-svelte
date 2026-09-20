<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5nmo0bcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="h5nmo0bcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:arrowheads-up-chevron" {...props}></Icon>
