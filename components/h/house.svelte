<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vw6r-lbms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vw6r-lbms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:house" {...props}></Icon>
