<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jcv9toj4y.css';
import '../../css/t/tgkamedfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jcv9toj4y"/><path class="tgkamedfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bonfire-20-bold" {...props}></Icon>
