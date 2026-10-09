<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b19q2ulep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="b19q2ulep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-big-down-20" {...props}></Icon>
