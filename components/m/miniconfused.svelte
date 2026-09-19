<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mssryabqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":768};
const content = `<path class="mssryabqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:miniconfused" {...props}></Icon>
