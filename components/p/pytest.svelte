<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a250hgbdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a250hgbdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:pytest" {...props}></Icon>
