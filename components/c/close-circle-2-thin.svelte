<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q0rxo6tin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q0rxo6tin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:close-circle-2-thin" {...props}></Icon>
