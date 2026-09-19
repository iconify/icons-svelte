<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1a2rhbxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="w1a2rhbxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:exchange" {...props}></Icon>
