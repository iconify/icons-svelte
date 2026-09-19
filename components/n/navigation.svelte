<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4fj2ibaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="l4fj2ibaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:navigation" {...props}></Icon>
