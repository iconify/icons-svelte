<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-3r6qbax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="z-3r6qbax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:maximize-1" {...props}></Icon>
