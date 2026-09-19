<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bn1u7cctv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bn1u7cctv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:arrow-right" {...props}></Icon>
