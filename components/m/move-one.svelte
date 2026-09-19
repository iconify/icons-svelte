<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fu8-imbge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fu8-imbge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:move-one" {...props}></Icon>
