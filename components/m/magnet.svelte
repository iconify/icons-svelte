<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jca6feb4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="jca6feb4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:magnet" {...props}></Icon>
