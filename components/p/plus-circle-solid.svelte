<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxqzcjb7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fxqzcjb7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:plus-circle-solid" {...props}></Icon>
