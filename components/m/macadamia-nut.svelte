<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_xj2ldud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="y_xj2ldud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:macadamia-nut" {...props}></Icon>
