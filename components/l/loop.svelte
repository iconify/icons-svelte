<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdtvnc2lo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hdtvnc2lo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:loop" {...props}></Icon>
