<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfpe-fj8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yfpe-fj8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="doodle-icons:bookmark" {...props}></Icon>
