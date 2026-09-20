<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/he90tkigr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="he90tkigr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:nuget" {...props}></Icon>
