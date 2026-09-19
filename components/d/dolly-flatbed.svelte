<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mn13ih9-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="mn13ih9-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:dolly-flatbed" {...props}></Icon>
