<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/dqwn18b1s.css';
import '../../css/s/s7f1fwbbg.css';
import '../../css/w/wotaafb6p.css';
import '../../css/o/o1cpgsbzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="dqwn18b1s"/><path clip-rule="evenodd" class="s7f1fwbbg"/><path class="wotaafb6p"/><path class="o1cpgsbzo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:card-search-bold-duotone" {...props}></Icon>
