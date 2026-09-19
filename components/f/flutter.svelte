<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9zm6abth.css';
import '../../css/h/ha140i38m.css';
import '../../css/c/cij3cro7f.css';
import '../../css/m/mthnz6bim.css';
import '../../css/i/izjyrbg3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":4.233,"height":4.233};
const content = `<g class="e9zm6abth"><path class="ha140i38m"/><path class="cij3cro7f"/><path class="mthnz6bim"/><path class="izjyrbg3z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:flutter" {...props}></Icon>
