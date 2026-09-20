<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/prwk1vbhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="prwk1vbhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:bluetooth-solid" {...props}></Icon>
