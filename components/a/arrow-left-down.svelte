<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4g-0aboz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s4g-0aboz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:arrow-left-down" {...props}></Icon>
