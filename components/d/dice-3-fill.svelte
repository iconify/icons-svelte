<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r09i3hofv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="r09i3hofv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:dice-3-fill" {...props}></Icon>
