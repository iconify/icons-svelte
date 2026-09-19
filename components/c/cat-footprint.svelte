<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3gh1kbsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o3gh1kbsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:cat-footprint" {...props}></Icon>
