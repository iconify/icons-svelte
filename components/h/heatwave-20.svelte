<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6zve7bwi.css';
import '../../css/k/ku1wiibua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="x6zve7bwi"/><path class="ku1wiibua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heatwave-20" {...props}></Icon>
