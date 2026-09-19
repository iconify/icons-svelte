<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/myddi0u4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="myddi0u4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:level-five-title" {...props}></Icon>
