<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h77o0gzdy.css';
import '../../css/u/uh9wjbc8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="h77o0gzdy"/><path class="uh9wjbc8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mug-20" {...props}></Icon>
