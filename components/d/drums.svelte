<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdyw14b1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kdyw14b1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:drums" {...props}></Icon>
