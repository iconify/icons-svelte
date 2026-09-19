<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/pp460t85i.css';
import '../../css/p/pdpz416em.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="pp460t85i"/><path class="pdpz416em"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ginetex:only-oxygen-bleach-allowed" {...props}></Icon>
