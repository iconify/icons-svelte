<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/np-sermtc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="np-sermtc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:four" {...props}></Icon>
