<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-io5hbcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="x-io5hbcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:link-in" {...props}></Icon>
