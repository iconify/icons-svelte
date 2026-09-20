<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8co3-b7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="f8co3-b7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:power" {...props}></Icon>
