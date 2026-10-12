<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/phgbpj4vk.css';
import '../../css/f/f20lr8brg.css';
import '../../css/s/s805e4aqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="phgbpj4vk"/><path class="f20lr8brg"/><path class="s805e4aqh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:hd-duotone" {...props}></Icon>
