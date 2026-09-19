<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/g/gsx59ilbo.css';
import '../../css/r/ro9sclw5a.css';
import '../../css/g/gmeghdcvi.css';
import '../../css/e/es8z9e5se.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="gsx59ilbo"/><path class="ro9sclw5a"/><path class="gmeghdcvi"/><path class="es8z9e5se"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="covid:graph-death-rate-stable" {...props}></Icon>
