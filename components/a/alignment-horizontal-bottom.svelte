<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vm3ivccum.css';
import '../../css/s/s8pacjbfa.css';
import '../../css/c/ch1x8bcvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="vm3ivccum"><rect class="s8pacjbfa"/><path class="ch1x8bcvk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:alignment-horizontal-bottom" {...props}></Icon>
