<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5exhlb3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="x5exhlb3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:right-small-down" {...props}></Icon>
