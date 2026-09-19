<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/c/cgm86oegm.css';
import '../../css/x/x7onvleiz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="cgm86oegm"/><path class="x7onvleiz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:number-1-square-thin" {...props}></Icon>
