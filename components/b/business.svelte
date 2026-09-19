<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xqvm3jumk.css';
import '../../css/x/x2fozm4ep.css';
import '../../css/f/fqwabbb6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xqvm3jumk"/><path class="x2fozm4ep"/><path class="fqwabbb6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:business" {...props}></Icon>
