<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k71_yo_lj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k71_yo_lj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bedside-table-2-fill" {...props}></Icon>
