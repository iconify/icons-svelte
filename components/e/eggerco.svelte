<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2d6budho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":843.89,"height":843.9};
const content = `<path class="n2d6budho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:eggerco" {...props}></Icon>
