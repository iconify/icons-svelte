<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_ulf57cv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="c_ulf57cv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:approval" {...props}></Icon>
