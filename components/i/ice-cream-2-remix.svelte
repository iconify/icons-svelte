<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3bux4e8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="k3bux4e8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:ice-cream-2-remix" {...props}></Icon>
