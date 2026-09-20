<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5sfl_b0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="y5sfl_b0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:glide-dark" {...props}></Icon>
