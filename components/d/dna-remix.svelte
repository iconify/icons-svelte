<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/poal0b8dc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="poal0b8dc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:dna-remix" {...props}></Icon>
