<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ornos409u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ornos409u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:quotes" {...props}></Icon>
