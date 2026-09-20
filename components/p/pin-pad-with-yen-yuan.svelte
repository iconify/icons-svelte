<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_izhyj8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="f_izhyj8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pin-pad-with-yen-yuan" {...props}></Icon>
