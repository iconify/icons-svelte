<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whhmhlbyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":60,"height":60};
const content = `<path clip-rule="evenodd" class="whhmhlbyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:manus-dark" {...props}></Icon>
