<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1_9j_biz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="w1_9j_biz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-big-right-48-bold" {...props}></Icon>
