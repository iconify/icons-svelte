<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oselk1bpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="oselk1bpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:arrow-right" {...props}></Icon>
