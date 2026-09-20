<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjxocub0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":28};
const content = `<path class="gjxocub0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:attio" {...props}></Icon>
