<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qaye-t6-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qaye-t6-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:parallelogram-20-bold" {...props}></Icon>
