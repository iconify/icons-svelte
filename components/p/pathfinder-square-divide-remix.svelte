<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pv931mb5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="pv931mb5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:pathfinder-square-divide-remix" {...props}></Icon>
