<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-lwpu35p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="w-lwpu35p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:minimize-20" {...props}></Icon>
