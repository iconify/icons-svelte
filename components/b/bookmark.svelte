<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ji2194_ef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="ji2194_ef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:bookmark" {...props}></Icon>
