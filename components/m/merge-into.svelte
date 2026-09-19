<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxuwllz5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gxuwllz5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:merge-into" {...props}></Icon>
