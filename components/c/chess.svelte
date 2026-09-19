<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8i_g0-3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="y8i_g0-3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:chess" {...props}></Icon>
