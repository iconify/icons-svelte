<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igzplx7gf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="igzplx7gf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:flagstick-with-flag" {...props}></Icon>
