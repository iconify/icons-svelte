<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mc5usib6x.css';
import '../../css/j/j2plu7b6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mc5usib6x"/><path class="j2plu7b6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:area-chart" {...props}></Icon>
