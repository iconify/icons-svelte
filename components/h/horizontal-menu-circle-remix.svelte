<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njf8bp8mn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="njf8bp8mn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:horizontal-menu-circle-remix" {...props}></Icon>
