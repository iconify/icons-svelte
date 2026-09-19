<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vt--b6bfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vt--b6bfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:done-all" {...props}></Icon>
