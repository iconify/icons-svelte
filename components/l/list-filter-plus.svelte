<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hylu2byvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hylu2byvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:list-filter-plus" {...props}></Icon>
