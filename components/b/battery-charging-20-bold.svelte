<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtljkfb6y.css';
import '../../css/t/tkx4pub6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jtljkfb6y"/><path class="tkx4pub6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-charging-20-bold" {...props}></Icon>
