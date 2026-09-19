<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lch49bcjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lch49bcjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:arrow-uturn-right-up" {...props}></Icon>
