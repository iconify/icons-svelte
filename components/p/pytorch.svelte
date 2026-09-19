<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zy86frb8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zy86frb8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:pytorch" {...props}></Icon>
