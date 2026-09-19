<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/aj5gz5b0j.css';
import '../../css/t/tontn-b1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":31,"height":32};
const content = `<g class="cuyn6tgcc"><path class="aj5gz5b0j"/><path class="tontn-b1j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:grid" {...props}></Icon>
