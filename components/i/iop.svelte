<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5tmsshmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="t5tmsshmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:iop" {...props}></Icon>
