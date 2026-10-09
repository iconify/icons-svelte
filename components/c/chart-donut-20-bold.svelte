<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aa6-c2yag.css';
import '../../css/i/ihj-8acvw.css';
import '../../css/b/bdln6g71h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="aa6-c2yag"/><path class="ihj-8acvw"/><path class="bdln6g71h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-donut-20-bold" {...props}></Icon>
