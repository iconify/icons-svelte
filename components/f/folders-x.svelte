<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ylzad086p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ylzad086p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:folders-x" {...props}></Icon>
