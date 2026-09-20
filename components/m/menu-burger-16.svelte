<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dm2dx0b1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dm2dx0b1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:menu-burger-16" {...props}></Icon>
