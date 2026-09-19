<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpc1n7bjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jpc1n7bjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:ctrl" {...props}></Icon>
