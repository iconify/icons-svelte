<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-x6w3ngg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":51.974,"height":20.409,"left":-0.578,"top":-0.578};
const content = `<path class="m-x6w3ngg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ola-cabs" {...props}></Icon>
