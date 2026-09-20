<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/f/fgw8jg94a.css';
import '../../css/h/hehoqx8il.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g class="y9tr6bcfx"><circle class="fgw8jg94a"/><path class="hehoqx8il"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-weather-celsius-degrees-temperature-centigrade-celsius-degree-weather" {...props}></Icon>
