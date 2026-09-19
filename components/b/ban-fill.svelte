<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1z-bmbon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="c1z-bmbon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:ban-fill" {...props}></Icon>
