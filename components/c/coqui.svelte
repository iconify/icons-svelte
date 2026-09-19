<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0_tc6b1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="x0_tc6b1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:coqui" {...props}></Icon>
