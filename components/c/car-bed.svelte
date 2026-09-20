<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x34kw6p8w.css';
import '../../css/b/bb0f4cb0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x34kw6p8w"/><path class="bb0f4cb0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:car-bed" {...props}></Icon>
