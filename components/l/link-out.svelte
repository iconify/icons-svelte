<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdvenognr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wdvenognr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:link-out" {...props}></Icon>
