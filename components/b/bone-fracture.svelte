<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9_cr7dkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="a9_cr7dkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:bone-fracture" {...props}></Icon>
