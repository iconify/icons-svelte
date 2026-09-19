<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jb46l2bag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jb46l2bag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:nmr" {...props}></Icon>
