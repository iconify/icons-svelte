<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukg4327zf.css';
import '../../css/h/hc8c97wzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ukg4327zf"/><path class="hc8c97wzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:map-20-bold" {...props}></Icon>
