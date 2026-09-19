<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlx2ab_yw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1792};
const content = `<path class="zlx2ab_yw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:bell-o" {...props}></Icon>
