<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cytz3vbrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="cytz3vbrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:crop-selection-remix" {...props}></Icon>
