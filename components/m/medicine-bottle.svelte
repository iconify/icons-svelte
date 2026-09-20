<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5eglmmgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="e5eglmmgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:medicine-bottle" {...props}></Icon>
