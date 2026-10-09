<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7aknm1gv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="t7aknm1gv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:loader-20-bold" {...props}></Icon>
