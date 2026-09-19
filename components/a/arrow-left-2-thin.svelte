<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2-id4-1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m2-id4-1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-left-2-thin" {...props}></Icon>
