<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdx1pbuzq.css';
import '../../css/d/dzwhzcc4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cdx1pbuzq"/><path class="dzwhzcc4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:relay-20-bold" {...props}></Icon>
