<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2-glub9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j2-glub9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:mirror-vertically" {...props}></Icon>
