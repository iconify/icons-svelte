<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwzn8jb7l.css';
import '../../css/x/xhaqngbdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bwzn8jb7l"/><path class="xhaqngbdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bandage-20" {...props}></Icon>
