<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fruy2eb-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fruy2eb-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:move-one" {...props}></Icon>
