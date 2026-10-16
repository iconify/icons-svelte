<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lj7euhm1y.css';
import '../../css/h/h17jzb6dy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lj7euhm1y"/><path class="h17jzb6dy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:data-pipeline-20-bold" {...props}></Icon>
