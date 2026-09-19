<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjw6k0b3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gjw6k0b3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:bcn" {...props}></Icon>
