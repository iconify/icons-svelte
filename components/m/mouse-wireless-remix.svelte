<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ky9cn3brn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ky9cn3brn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:mouse-wireless-remix" {...props}></Icon>
