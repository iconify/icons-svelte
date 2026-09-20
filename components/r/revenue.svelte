<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wetfdac9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="wetfdac9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:revenue" {...props}></Icon>
