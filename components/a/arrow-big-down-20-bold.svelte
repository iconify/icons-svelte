<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eede2abzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="eede2abzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-big-down-20-bold" {...props}></Icon>
