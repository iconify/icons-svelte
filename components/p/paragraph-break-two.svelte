<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aa9-8fuis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="aa9-8fuis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:paragraph-break-two" {...props}></Icon>
