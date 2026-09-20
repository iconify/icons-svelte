<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fab146hml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fab146hml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:phpstorm" {...props}></Icon>
