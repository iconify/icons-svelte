<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgi1rwuzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="mgi1rwuzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:recycle-bin-3-remix" {...props}></Icon>
