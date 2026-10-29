<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o20mlz1qj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o20mlz1qj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:grip-horizontal" {...props}></Icon>
