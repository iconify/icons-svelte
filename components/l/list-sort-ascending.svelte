<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3_apj8zv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d3_apj8zv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:list-sort-ascending" {...props}></Icon>
