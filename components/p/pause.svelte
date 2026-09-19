<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvu6jpbwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fvu6jpbwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:pause" {...props}></Icon>
