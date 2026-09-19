<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbnr73vgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="mbnr73vgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:brightness" {...props}></Icon>
