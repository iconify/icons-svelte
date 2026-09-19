<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rh3sju-sz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="rh3sju-sz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:correct" {...props}></Icon>
