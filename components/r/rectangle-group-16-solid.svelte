<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/as8c1x0lp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="as8c1x0lp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:rectangle-group-16-solid" {...props}></Icon>
