<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pu6k__gts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="pu6k__gts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:intellectual-solid" {...props}></Icon>
