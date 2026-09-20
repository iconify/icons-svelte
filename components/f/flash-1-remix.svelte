<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxeirhb_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="mxeirhb_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:flash-1-remix" {...props}></Icon>
