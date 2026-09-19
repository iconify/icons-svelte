<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ol1qgland.css';
import '../../css/l/lu-nqrbmy.css';
import '../../css/a/ayje7ibqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ol1qgland"><path class="lu-nqrbmy"/><path class="ayje7ibqv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:intermediate-mode" {...props}></Icon>
