<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sg0altbfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sg0altbfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:excalidraw" {...props}></Icon>
