<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpycbh9ox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jpycbh9ox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:arrow-axes" {...props}></Icon>
