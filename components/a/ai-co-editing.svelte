<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/g/ggclseb0g.css';
import '../../css/o/of4mc-rsl.css';
import '../../css/f/f-axaw8df.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ggclseb0g"/><circle class="of4mc-rsl"/><path class="f-axaw8df"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:ai-co-editing" {...props}></Icon>
