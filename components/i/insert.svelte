<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhffbwces.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hhffbwces"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:insert" {...props}></Icon>
