<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itw0z-bdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="itw0z-bdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:map-fold-remix" {...props}></Icon>
