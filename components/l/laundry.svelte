<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxstgrz9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pxstgrz9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:laundry" {...props}></Icon>
