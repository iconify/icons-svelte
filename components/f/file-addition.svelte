<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8-v5vbxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="h8-v5vbxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:file-addition" {...props}></Icon>
