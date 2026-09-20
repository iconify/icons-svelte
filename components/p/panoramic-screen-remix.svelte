<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ryotqrb_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ryotqrb_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:panoramic-screen-remix" {...props}></Icon>
