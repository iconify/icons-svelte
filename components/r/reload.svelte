<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mo071dbej.css';
import '../../css/a/apap_ab6a.css';
import '../../css/w/w3a_f7b_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="mo071dbej"/><path class="apap_ab6a"/><path class="w3a_f7b_k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:reload" {...props}></Icon>
