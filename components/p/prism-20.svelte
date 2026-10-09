<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g277awvop.css';
import '../../css/x/x00tm8b5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="g277awvop"/><path class="x00tm8b5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:prism-20" {...props}></Icon>
