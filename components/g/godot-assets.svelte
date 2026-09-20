<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmkq3nmdi.css';
import '../../css/g/g2yfz6ydr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jmkq3nmdi"/><path class="g2yfz6ydr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:godot-assets" {...props}></Icon>
