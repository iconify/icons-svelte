<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/tti9u7bvi.css';
import '../../css/b/ba138mb_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="tti9u7bvi"/><path class="ba138mb_t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:quote-duotone" {...props}></Icon>
