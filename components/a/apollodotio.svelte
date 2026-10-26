<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlnwz7iwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":303,"height":303};
const content = `<path class="zlnwz7iwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:apollodotio" {...props}></Icon>
