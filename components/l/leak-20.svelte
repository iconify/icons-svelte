<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/blu3__1ct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="blu3__1ct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:leak-20" {...props}></Icon>
