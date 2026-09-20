<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/o5wplb8az.css';
import '../../css/v/vh953qb-o.css';
import '../../css/n/n3064hbxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="o5wplb8az"/><path clip-rule="evenodd" class="vh953qb-o"/><path class="n3064hbxs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:mask-happy" {...props}></Icon>
