<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/r/rzg7m5suh.css';
import '../../css/x/x_0h1kjap.css';
import '../../css/u/u-julac8y.css';
import '../../css/h/hf0bzw-qm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="rzg7m5suh wm-k"/><path class="wm-shadow x_0h1kjap"/><path class="u-julac8y wm-k"/><path class="hf0bzw-qm wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:baby-bottle-engrave" {...props}></Icon>
