<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezkmt2vox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":384};
const content = `<path class="ezkmt2vox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:cast-connected" {...props}></Icon>
