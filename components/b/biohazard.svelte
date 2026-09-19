<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tu-4c3b4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="tu-4c3b4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:biohazard" {...props}></Icon>
