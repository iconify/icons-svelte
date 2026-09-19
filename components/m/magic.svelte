<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkwely5ns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pkwely5ns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:magic" {...props}></Icon>
