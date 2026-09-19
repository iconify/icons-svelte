<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y2u1amfii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="y2u1amfii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:filter" {...props}></Icon>
