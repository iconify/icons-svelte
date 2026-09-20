<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwi_mlb7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="qwi_mlb7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:appcelerator" {...props}></Icon>
