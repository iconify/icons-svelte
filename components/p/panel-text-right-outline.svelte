<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/s9hzd3eul.css';
import '../../css/h/hr0kstbnd.css';
import '../../css/k/kpikqbbuv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="s9hzd3eul"/><path class="hr0kstbnd"/><path clip-rule="evenodd" class="kpikqbbuv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:panel-text-right-outline" {...props}></Icon>
