<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mkksefj0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="mkksefj0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:camera-1-remix" {...props}></Icon>
