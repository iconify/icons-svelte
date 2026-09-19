<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ml8m9nuev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ml8m9nuev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:avianex" {...props}></Icon>
