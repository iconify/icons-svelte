<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/s84hulbte.css';
import '../../css/r/rz7rcac5k.css';
import '../../css/o/oasgoj2dk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<g class="cuyn6tgcc"><path class="s84hulbte"/><path class="rz7rcac5k"/><path class="oasgoj2dk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:periscope-circle" {...props}></Icon>
