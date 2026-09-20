<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx_c6ibit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jx_c6ibit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:connect" {...props}></Icon>
