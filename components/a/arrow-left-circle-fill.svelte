<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztd29dblt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ztd29dblt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:arrow-left-circle-fill" {...props}></Icon>
