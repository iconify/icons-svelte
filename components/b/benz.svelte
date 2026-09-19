<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/y/y6f0jibvm.css';
import '../../css/x/xlg4h1uyo.css';
import '../../css/b/bazc4or7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path class="y6f0jibvm"/><path class="xlg4h1uyo"/><path class="bazc4or7p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:benz" {...props}></Icon>
