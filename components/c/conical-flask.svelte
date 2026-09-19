<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9qhx1bfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="r9qhx1bfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:conical-flask" {...props}></Icon>
