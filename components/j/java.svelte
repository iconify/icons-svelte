<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udv3r3bwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="udv3r3bwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:java" {...props}></Icon>
