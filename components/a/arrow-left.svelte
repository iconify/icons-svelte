<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9789pzfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="z9789pzfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:arrow-left" {...props}></Icon>
