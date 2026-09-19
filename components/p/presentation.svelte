<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/ji87fobic.css';
import '../../css/i/ijwx40j8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":31,"height":32};
const content = `<g class="cuyn6tgcc"><path class="ji87fobic"/><path class="ijwx40j8g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:presentation" {...props}></Icon>
