<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbpt-4e8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="kbpt-4e8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:location-pin-3-remix" {...props}></Icon>
